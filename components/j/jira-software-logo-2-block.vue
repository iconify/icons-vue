<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brw66jb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="brw66jb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:jira-software-logo-2-block" /></template>
