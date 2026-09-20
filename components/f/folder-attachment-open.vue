<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urvd_efow.css';
import '../../css/i/iqsbobj2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="urvd_efow"/><path class="iqsbobj2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-attachment-open" /></template>
