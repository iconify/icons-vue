<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hya0m4b1r.css';
import '../../css/u/utm1ftb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hya0m4b1r wm-k"/><path class="utm1ftb-c wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:candy-cane" /></template>
