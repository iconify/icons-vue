<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knmkkbbxd.css';
import '../../css/y/yp1z57b0r.css';
import '../../css/c/cep230_ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knmkkbbxd"/><path class="yp1z57b0r"/><path class="cep230_ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:droplet" /></template>
