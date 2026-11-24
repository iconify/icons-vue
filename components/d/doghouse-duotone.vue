<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/msv92hb5b.css';
import '../../css/h/h8po8dbte.css';
import '../../css/b/bwvpembku.css';
import '../../css/s/sxt9xbc4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="msv92hb5b"/><path class="h8po8dbte"/><path class="bwvpembku"/><path class="sxt9xbc4k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:doghouse-duotone" /></template>
