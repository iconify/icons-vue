<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbw59hkqr.css';
import '../../css/u/u19mxjbnb.css';
import '../../css/k/k16fi-_we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbw59hkqr"/><path class="u19mxjbnb"/><path class="k16fi-_we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:image-alt" /></template>
