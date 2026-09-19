<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yui9jhbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yui9jhbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:lampalt" /></template>
