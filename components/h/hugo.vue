<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb3m88byk.css';
import '../../css/b/ba1fozbwm.css';
import '../../css/v/v3or5zb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kb3m88byk"/><path class="ba1fozbwm"/><path class="v3or5zb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:hugo" /></template>
