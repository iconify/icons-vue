<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1du9-b5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z1du9-b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-latin-filled" /></template>
