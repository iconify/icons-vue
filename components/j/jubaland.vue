<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvdemeinh.css';
import '../../css/z/zu4nqpm5c.css';
import '../../css/m/mfzwz5b6g.css';
import '../../css/v/v24hg-b_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="vvdemeinh"/><path class="zu4nqpm5c"/><path class="mfzwz5b6g"/><path class="v24hg-b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:jubaland" /></template>
