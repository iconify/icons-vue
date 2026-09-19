<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s88sv1bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":350,"height":512};
const content = `<path class="s88sv1bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:hack" /></template>
