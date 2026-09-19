<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nazj7-39k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="nazj7-39k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:envelope-small-filled" /></template>
