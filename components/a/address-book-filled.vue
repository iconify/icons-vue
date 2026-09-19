<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y012yebaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="y012yebaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:address-book-filled" /></template>
