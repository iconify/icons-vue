<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-qdqubtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="b-qdqubtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:asciidoctor" /></template>
