<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu9cahcli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu9cahcli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:briefcase-medical-solid" /></template>
