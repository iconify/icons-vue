<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpqnhmtil.css';
import '../../css/x/x42oxcctk.css';
import '../../css/h/hwh4m4bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wpqnhmtil"/><path clip-rule="evenodd" class="x42oxcctk"/><path clip-rule="evenodd" class="hwh4m4bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:instagram-logo" /></template>
