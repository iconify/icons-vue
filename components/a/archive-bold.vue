<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x--eq7b-p.css';
import '../../css/s/s6dl6st5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x--eq7b-p"/><path class="s6dl6st5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-bold" /></template>
