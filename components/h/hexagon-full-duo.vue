<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4s9j0-ru.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b00ennbgq.css';
import '../../css/o/otnhmebbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4s9j0-ru secondary"/><g class="dt0cm9dhy primary"><path class="b00ennbgq"/><path class="otnhmebbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hexagon-full-duo" /></template>
