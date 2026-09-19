<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac4r5ub6d.css';
import '../../css/l/lwgbjb0jl.css';
import '../../css/f/fjpj-53lj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac4r5ub6d"/><path class="lwgbjb0jl"/><path class="fjpj-53lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-shell" /></template>
