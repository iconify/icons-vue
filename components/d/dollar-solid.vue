<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7kpp74tp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7kpp74tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dollar-solid" /></template>
