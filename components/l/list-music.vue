<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt79rrb-y.css';
import '../../css/t/th0jcu54c.css';
import '../../css/u/ugxrr-hjp.css';
import '../../css/n/n2q0nac6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt79rrb-y wm-k"/><path class="th0jcu54c wm-a"/><path class="ugxrr-hjp wm-a"/><path class="n2q0nac6i wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:list-music" /></template>
