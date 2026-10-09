<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmhhpqmkw.css';
import '../../css/b/b0flmi83f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jmhhpqmkw"/><path class="b0flmi83f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-right-20-bold" /></template>
