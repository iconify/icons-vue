<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au98x5bva.css';
import '../../css/t/toacpk17o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au98x5bva"/><path class="toacpk17o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-archive" /></template>
