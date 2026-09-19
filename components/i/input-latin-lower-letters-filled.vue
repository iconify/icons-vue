<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfzxfn1ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lfzxfn1ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:input-latin-lower-letters-filled" /></template>
