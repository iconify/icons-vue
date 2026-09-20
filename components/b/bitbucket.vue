<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io988ibmp.css';
import '../../css/r/r02pwbbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io988ibmp"/><path class="r02pwbbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bitbucket" /></template>
