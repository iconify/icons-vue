<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh3g_jboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh3g_jboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-g-circle-solid" /></template>
