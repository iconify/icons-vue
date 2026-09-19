<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3j_08rws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="p3j_08rws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:disqus" /></template>
