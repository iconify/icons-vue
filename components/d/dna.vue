<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk_1psu1o.css';
import '../../css/g/gx-lz3vja.css';
import '../../css/d/dj2mub87f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk_1psu1o wm-a"/><path class="gx-lz3vja wm-k"/><path class="dj2mub87f wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:dna" /></template>
