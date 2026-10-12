<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnvtau33l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vnvtau33l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:logo-google-drive-20" /></template>
