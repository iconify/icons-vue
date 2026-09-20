<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qns_s2bni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qns_s2bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:function-filled" /></template>
