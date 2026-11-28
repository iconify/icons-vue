<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqzrm9bdh.css';
import '../../css/u/ur_vkvbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqzrm9bdh secondary"/><path class="primary ur_vkvbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-stored-data-duo" /></template>
