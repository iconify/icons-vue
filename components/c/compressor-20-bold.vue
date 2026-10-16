<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj6o68bgt.css';
import '../../css/w/wcxlfdb-u.css';
import '../../css/b/bi2qc8bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cj6o68bgt"/><path class="wcxlfdb-u"/><path class="bi2qc8bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:compressor-20-bold" /></template>
