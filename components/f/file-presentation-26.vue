<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-ln0mbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":26};
const content = `<path class="f-ln0mbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-presentation-26" /></template>
