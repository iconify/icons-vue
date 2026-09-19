<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe7gk_bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xe7gk_bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:cpanel" /></template>
