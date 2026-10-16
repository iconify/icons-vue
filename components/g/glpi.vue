<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-nrwr6-l.css';
import '../../css/p/pbbp6tybj.css';
import '../../css/u/u4nf05b9r.css';
import '../../css/o/ov1_56bin.css';
import '../../css/a/act7vhwso.css';
import '../../css/y/ymvf5wbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":216,"height":92};
const content = `<path class="f-nrwr6-l"/><path class="pbbp6tybj"/><path class="u4nf05b9r"/><path class="ov1_56bin"/><path class="act7vhwso"/><path class="ymvf5wbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:glpi" /></template>
