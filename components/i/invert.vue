<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p31nrpb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="p31nrpb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:invert" /></template>
