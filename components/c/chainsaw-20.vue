<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq3f9xb0h.css';
import '../../css/v/vkpsfpb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nq3f9xb0h"/><path class="vkpsfpb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chainsaw-20" /></template>
