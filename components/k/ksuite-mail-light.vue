<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2j0xjy7g.css';
import '../../css/b/bdp2a1_-z.css';
import '../../css/d/d7fm7dbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f2j0xjy7g"/><path class="bdp2a1_-z"/><path class="d7fm7dbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-mail-light" /></template>
