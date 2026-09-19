<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcakmyo1t.css';
import '../../css/s/s9yq9kbzh.css';
import '../../css/a/asyevsbiz.css';
import '../../css/d/dehbkrbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rcakmyo1t"/><path class="s9yq9kbzh"/><path class="asyevsbiz"/><g><path class="dehbkrbqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-watch" /></template>
