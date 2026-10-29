<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex4-6yb8i.css';
import '../../css/b/b299m9_ij.css';
import '../../css/b/b95jh0dhy.css';
import '../../css/v/v9v-_db3h.css';
import '../../css/x/x9buy5b-v.css';
import '../../css/x/xxiywab7g.css';
import '../../css/b/bozk8nbgg.css';
import '../../css/k/k-kfo7bga.css';
import '../../css/c/cz5_zkb8h.css';
import '../../css/u/uqj6zmb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex4-6yb8i wm-shadow"/><path class="b299m9_ij"/><path class="b95jh0dhy"/><path class="v9v-_db3h"/><path class="x9buy5b-v"/><path class="wm-shine xxiywab7g"/><path class="bozk8nbgg"/><path class="k-kfo7bga"/><path class="cz5_zkb8h"/><path class="uqj6zmb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-plush:avatar-dino" /></template>
