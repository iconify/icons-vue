<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_qag_boy.css';
import '../../css/i/ik464kqyv.css';
import '../../css/o/okefe65_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_qag_boy"/><path class="ik464kqyv"/><path class="okefe65_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fctr" /></template>
