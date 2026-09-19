<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1ccnp3iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l1ccnp3iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:algolia" /></template>
