<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn16o9_6z.css';
import '../../css/j/jsf9fd5pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn16o9_6z"/><path clip-rule="evenodd" class="jsf9fd5pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bike" /></template>
