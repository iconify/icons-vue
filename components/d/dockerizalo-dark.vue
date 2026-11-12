<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjq4rwesi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jjq4rwesi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dockerizalo-dark" /></template>
