<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqualhbgp.css';
import '../../css/v/v_pt9ob9w.css';
import '../../css/d/dcu62ebsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="gqualhbgp"/><path class="v_pt9ob9w"/><path class="dcu62ebsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:horizontal-black-octagon" /></template>
