<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knf-jaczf.css';
import '../../css/z/zakcsrw3t.css';
import '../../css/m/m_hfkybog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="knf-jaczf"/><rect class="zakcsrw3t"/><path class="m_hfkybog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:gift-outline" /></template>
