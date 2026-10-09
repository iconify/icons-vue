<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkzs98bzj.css';
import '../../css/a/ajl3hnenw.css';
import '../../css/f/fq_nbabag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kkzs98bzj"/><path class="ajl3hnenw"/><path class="fq_nbabag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:git-merge-48" /></template>
