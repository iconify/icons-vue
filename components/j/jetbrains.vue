<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqd53454f.css';
import '../../css/t/ttzgexr7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lqd53454f"/><path class="ttzgexr7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:jetbrains" /></template>
