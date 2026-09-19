<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cci33jb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cci33jb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:comment" /></template>
