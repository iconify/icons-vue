<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6ieu0cyc.css';
import '../../css/z/z972og84a.css';
import '../../css/q/qy4unhbqf.css';
import '../../css/i/iy8nfbbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="u6ieu0cyc"/><rect class="z972og84a"/><rect class="qy4unhbqf"/><rect class="iy8nfbbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:apps" /></template>
