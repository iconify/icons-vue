<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvkn9c3_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:broken-pottery" /></template>
<style>
.hvkn9c3_e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.556 3.32q-1.228-.283-2.112.616q-.883.899-.578 2.122l.696 2.784q.316 1.26 1.565 1.617l1.207.345q.904.258 1.723-.203q.818-.462 1.066-1.369l.69-2.53q.252-.924-.24-1.746q-.491-.822-1.424-1.038zM3.22 6.898L7.057 4.02q.863-.647 1.907-.38t1.491 1.248l1.338 2.945q.585 1.286-.32 2.371l-1.381 1.657q-.257.31-.142.695l.84 2.802q.643 2.14-1.494 2.797l-3.307 1.018q-1.025.315-1.916-.282q-.89-.597-.987-1.665l-.757-8.324q-.114-1.251.891-2.004m11.932 5.744l3.028-.275q1.878-.171 2.375 1.649l.845 3.101q.485 1.779-1.164 2.604l-2.093 1.046q-1.211.606-2.314-.182l-2.049-1.463q-1.075-.767-.928-2.08l.268-2.408q.203-1.826 2.032-1.992");
}

</style>
