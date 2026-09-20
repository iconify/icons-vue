<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1jbzv3dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r1jbzv3dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:jira-software-logo-2-solid" /></template>
