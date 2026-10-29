<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu8p1jyfm.css';
import '../../css/c/c_91fblln.css';
import '../../css/w/wguz-gn9t.css';
import '../../css/p/pq-qeybii.css';
import '../../css/n/nyq9c63pw.css';
import '../../css/b/bj1_8bb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu8p1jyfm wm-shadow"/><path class="c_91fblln wm-k"/><path class="wguz-gn9t wm-k"/><path class="pq-qeybii wm-k"/><path class="nyq9c63pw wm-k"/><path class="bj1_8bb3v wm-shine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:check" /></template>
