<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kunthyb0f.css';
import '../../css/b/bzghj2btg.css';
import '../../css/d/dph_j-9vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kunthyb0f"/><path class="bzghj2btg"/><path class="dph_j-9vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:knexjs-wordmark" /></template>
