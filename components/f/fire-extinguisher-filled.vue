<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayq_smivk.css';
import '../../css/h/ht6zbmbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayq_smivk"/><path clip-rule="evenodd" class="ht6zbmbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:fire-extinguisher-filled" /></template>
