<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezuxa926a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ezuxa926a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-font-small-filled" /></template>
