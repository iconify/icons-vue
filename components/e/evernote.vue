<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgyb2p1_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jgyb2p1_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:evernote" /></template>
