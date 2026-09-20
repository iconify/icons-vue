<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxuwrvesc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rxuwrvesc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:indent-decrease-outline" /></template>
