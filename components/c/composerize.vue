<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bggzpxb-r.css';
import '../../css/a/acxb7gn1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bggzpxb-r"/><path class="acxb7gn1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:composerize" /></template>
