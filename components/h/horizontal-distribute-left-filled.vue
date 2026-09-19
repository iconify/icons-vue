<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m64_6gi5u.css';
import '../../css/h/hpml1nxgd.css';
import '../../css/z/zvvso5rkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m64_6gi5u"/><rect class="hpml1nxgd"/><rect class="zvvso5rkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:horizontal-distribute-left-filled" /></template>
