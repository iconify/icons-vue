<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-iiisbix.css';
import '../../css/b/brwrshb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-iiisbix"/><path clip-rule="evenodd" class="brwrshb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:info-rect-outline" /></template>
