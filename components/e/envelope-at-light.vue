<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djdujaclh.css';
import '../../css/p/pgkbw5buh.css';
import '../../css/e/eklvps3uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djdujaclh"/><path class="pgkbw5buh"/><path class="eklvps3uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:envelope-at-light" /></template>
