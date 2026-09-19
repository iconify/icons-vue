<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqugpjbox.css';
import '../../css/o/ohddqdbak.css';
import '../../css/k/kfydo0bxj.css';
import '../../css/c/cvhp0drkw.css';
import '../../css/p/pdq_5pb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mqugpjbox"/><g class="ohddqdbak"><path class="kfydo0bxj"/><path class="cvhp0drkw"/></g><path class="pdq_5pb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:data-encryption" /></template>
