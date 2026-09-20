<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v38f_4jkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v38f_4jkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:ember" /></template>
