<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3__ojbef.css';
import '../../css/d/dwrhhxelk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3__ojbef"/><path clip-rule="evenodd" class="dwrhhxelk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-letter-q-filled" /></template>
