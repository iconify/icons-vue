<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptysjpnfo.css';
import '../../css/z/z3hk8xbow.css';
import '../../css/y/yadmzfb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ptysjpnfo"/><path class="z3hk8xbow"/><path class="yadmzfb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:fsharp" /></template>
