<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gksx-9i4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":340,"height":512};
const content = `<path class="gksx-9i4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:figma" /></template>
