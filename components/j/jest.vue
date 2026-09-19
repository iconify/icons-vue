<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au_eukbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":450,"height":512};
const content = `<path class="au_eukbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:jest" /></template>
