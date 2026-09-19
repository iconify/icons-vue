<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvbubjb1v.css';
import '../../css/p/pj85_iwji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvbubjb1v"/><path class="pj85_iwji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-phone-incoming" /></template>
