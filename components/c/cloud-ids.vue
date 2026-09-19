<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp5ecabad.css';
import '../../css/y/ydng6ub1v.css';
import '../../css/o/omk7q06vg.css';
import '../../css/c/ceddezowq.css';
import '../../css/g/gxa31hbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp5ecabad"/><path class="ydng6ub1v"/><path class="omk7q06vg"/><path class="ceddezowq"/><path class="gxa31hbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-ids" /></template>
