<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4akmytgw.css';
import '../../css/u/uojfr4gpw.css';
import '../../css/r/rb_4au9oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4akmytgw"/><path clip-rule="evenodd" class="uojfr4gpw"/><path class="rb_4au9oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-cog-filled" /></template>
