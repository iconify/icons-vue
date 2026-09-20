<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdzjk4bvt.css';
import '../../css/o/osqzglbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qdzjk4bvt"/><path clip-rule="evenodd" class="osqzglbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:keyboard-16" /></template>
