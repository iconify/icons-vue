<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b80592p_t.css';
import '../../css/b/b1k_d4bpa.css';
import '../../css/f/fpu345b5a.css';
import '../../css/i/i6_9ppfpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b80592p_t"/><path class="b1k_d4bpa"/><path class="fpu345b5a"/><path class="i6_9ppfpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:geeq" /></template>
