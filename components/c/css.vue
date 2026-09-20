<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dyanzub4e.css';
import '../../css/u/udx94hb3b.css';
import '../../css/o/oenk4v16u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="dyanzub4e"/><path class="udx94hb3b"/><path class="oenk4v16u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="skill-icons:css" /></template>
