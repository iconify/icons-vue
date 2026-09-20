<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpumycc1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qpumycc1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:briefcase4" /></template>
