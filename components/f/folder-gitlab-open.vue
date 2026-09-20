<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k51-r1btv.css';
import '../../css/l/lhgt1qzum.css';
import '../../css/m/m023sbovp.css';
import '../../css/f/fyazefb-a.css';
import '../../css/o/oz3vbfwze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k51-r1btv"/><path class="lhgt1qzum"/><path class="m023sbovp"/><path class="fyazefb-a"/><path class="oz3vbfwze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-gitlab-open" /></template>
