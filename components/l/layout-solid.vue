<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pexotq5ng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pexotq5ng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:layout-solid" /></template>
