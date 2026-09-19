<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1soy6buh.css';
import '../../css/c/cbl4o-biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="r1soy6buh"/><path class="cbl4o-biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:kaldi" /></template>
