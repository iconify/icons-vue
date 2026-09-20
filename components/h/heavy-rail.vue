<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt-t8abnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pt-t8abnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:heavy-rail" /></template>
