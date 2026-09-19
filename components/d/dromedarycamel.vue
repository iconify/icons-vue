<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/heyc8pb-z.css';
import '../../css/a/a6xuroieo.css';
import '../../css/d/d98q5ca3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="heyc8pb-z"/><path class="a6xuroieo"/><path class="d98q5ca3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:dromedarycamel" /></template>
