<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyk60-btd.css';
import '../../css/j/jcbj2xbrn.css';
import '../../css/x/xe8-vm0oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyk60-btd"/><path class="jcbj2xbrn"/><path class="xe8-vm0oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-sync-filled" /></template>
