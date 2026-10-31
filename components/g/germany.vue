<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi1m_fwmt.css';
import '../../css/y/y55zcjfsz.css';
import '../../css/a/a_hbmibzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="bi1m_fwmt"/><path class="y55zcjfsz"/><path class="a_hbmibzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:germany" /></template>
