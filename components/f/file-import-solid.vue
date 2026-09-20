<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayoxpmbui.css';
import '../../css/e/ex6n6ltjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayoxpmbui"/><path class="ex6n6ltjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:file-import-solid" /></template>
