<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaslzfbmc.css';
import '../../css/x/x_1t_ybrw.css';
import '../../css/l/lnt4cbcsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qaslzfbmc"/><path clip-rule="evenodd" class="x_1t_ybrw"/><path class="lnt4cbcsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dep" /></template>
