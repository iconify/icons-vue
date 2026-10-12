<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5cvq3b4h.css';
import '../../css/i/iv92ody-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x5cvq3b4h"/><path class="iv92ody-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bug-off-filled" /></template>
