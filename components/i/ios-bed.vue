<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0po3xb8t.css';
import '../../css/b/bsha2ob5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x0po3xb8t"/><path class="bsha2ob5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-bed" /></template>
