<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4a081laz.css';
import '../../css/s/soh0llxrd.css';
import '../../css/f/f59zn7b2d.css';
import '../../css/x/x0-j_jb7w.css';
import '../../css/c/c-mizp4ta.css';
import '../../css/f/fuhbdfl6d.css';
import '../../css/e/etou4pd5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4a081laz"/><path class="soh0llxrd"/><path class="f59zn7b2d"/><path class="x0-j_jb7w"/><path class="c-mizp4ta"/><path class="fuhbdfl6d"/><path class="etou4pd5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:google-kubernetes-engine" /></template>
