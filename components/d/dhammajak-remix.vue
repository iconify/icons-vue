<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx4n9abmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gx4n9abmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:dhammajak-remix" /></template>
