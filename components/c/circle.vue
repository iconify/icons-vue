<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maimo8bna.css';
import '../../css/i/ia25_fnjm.css';
import '../../css/t/t70_dbc9x.css';
import '../../css/s/s1e2gibpn.css';
import '../../css/e/e9tz1vbtf.css';
import '../../css/j/j_dt9fb7r.css';
import '../../css/s/s03w5k5hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="maimo8bna wm-shadow"/><path class="ia25_fnjm"/><path class="t70_dbc9x"/><path class="s1e2gibpn"/><path class="e9tz1vbtf"/><path class="j_dt9fb7r wm-shine"/><path class="s03w5k5hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-plush:circle" /></template>
