<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z49l83-sf.css';
import '../../css/o/o9np2sbrl.css';
import '../../css/f/frlh8xbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z49l83-sf"/><path class="o9np2sbrl"/><path class="frlh8xbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mail-check-20-bold" /></template>
