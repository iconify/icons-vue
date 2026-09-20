<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih0nrxghi.css';
import '../../css/q/qy6r87b-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih0nrxghi"/><path class="qy6r87b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:left-indent-alt" /></template>
