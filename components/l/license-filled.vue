<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku6a_wbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku6a_wbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:license-filled" /></template>
