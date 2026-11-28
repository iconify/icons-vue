<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlznw-a5v.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b00ennbgq.css';
import '../../css/d/dbfl50qks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary tlznw-a5v"/><g class="dt0cm9dhy primary"><path class="b00ennbgq"/><path class="dbfl50qks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hexagon-third-duo" /></template>
