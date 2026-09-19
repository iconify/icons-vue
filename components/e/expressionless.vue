<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gshe_di8n.css';
import '../../css/v/vpfegd3_c.css';
import '../../css/s/s18lac6xp.css';
import '../../css/d/dispmjy6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gshe_di8n"/><path class="vpfegd3_c"/><path class="s18lac6xp"/><path class="dispmjy6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:expressionless" /></template>
