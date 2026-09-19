<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccug79xbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ccug79xbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:config-coffeescript" /></template>
