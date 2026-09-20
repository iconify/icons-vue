<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl0qbld8c.css';
import '../../css/b/brwqg6bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sl0qbld8c"/><path class="brwqg6bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-vm" /></template>
