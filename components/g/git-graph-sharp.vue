<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owknalbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owknalbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-graph-sharp" /></template>
