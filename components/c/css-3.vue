<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":361};
const content = `<path class="du0lyno7g"/><path class="t4e8ey98t"/><path class="iike1tbox"/><path class="dp8zczjwq"/><path class="lpe12sb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:css-3" /></template>
<style>
.dp8zczjwq {
  d: path("M60.484 0h38.68v16.176H76.66v16.176h22.506v16.175H60.484zm46.417 0h38.681v14.066h-22.505v2.813h22.505v32.352h-38.68V34.46h22.505v-2.813H106.9zm46.418 0H192v14.066h-22.505v2.813H192v32.352h-38.681V34.46h22.505v-2.813H153.32z");
}

.du0lyno7g {
  fill: var(--svg-color--264de4, #264DE4);
  d: path("M127.844 360.088L23.662 331.166L.445 70.766h255.11l-23.241 260.36z");
}

.iike1tbox {
  fill: var(--svg-color--ebebeb, #EBEBEB);
  d: path("m53.669 188.636l2.862 31.937H128v-31.937zm-5.752-64.641l2.903 31.937H128v-31.937zM128 271.58l-.14.037l-35.568-9.604l-2.274-25.471h-32.06l4.474 50.146l65.421 18.16l.147-.04z");
}

.lpe12sb6b {
  fill: var(--svg-color--fff, #FFF);
  d: path("m202.127 188.636l5.765-64.641H127.89v31.937h45.002l-2.906 32.704H127.89v31.937h39.327l-3.708 41.42l-35.62 9.614v33.226l65.473-18.145l.48-5.396l7.506-84.08z");
}

.t4e8ey98t {
  fill: var(--svg-color--2965f1, #2965F1);
  d: path("m212.417 314.547l19.86-222.49H128V337.95z");
}

</style>
