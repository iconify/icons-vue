<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_j4mhb6r.css';
import '../../css/m/m_f_sobnp.css';
import '../../css/y/yi_zyo09o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_j4mhb6r"/><rect class="m_f_sobnp"/><rect class="yi_zyo09o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:horizontal-align-right-filled" /></template>
