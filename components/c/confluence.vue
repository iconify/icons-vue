<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp7a4ne3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bp7a4ne3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:confluence" /></template>
