<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3qq0hx9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="v3qq0hx9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:chakraui" /></template>
