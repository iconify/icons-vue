<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlk7lo_3f.css';
import '../../css/d/dpz_dlb6v.css';
import '../../css/z/zn3-vg4ug.css';
import '../../css/l/lx930cc5o.css';
import '../../css/b/b0h4k8bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zlk7lo_3f"/><path class="dpz_dlb6v"/><path class="zn3-vg4ug"/><path class="lx930cc5o"/><path class="b0h4k8bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:ladder" /></template>
