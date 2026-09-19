<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vu30ywsla"/><path class="o9olt0bzh"/><path class="qkgxembuy"/><path class="riw60my_f"/><path class="o5s84ubrf"/><path class="kygipm52i"/><path class="biysuqhkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-south-africa" /></template>
<style>
.biysuqhkj {
  fill: var(--svg-color--dbad2b, #dbad2b);
  d: path("M.367 17.684c-.217.932-.322 1.923-.347 2.943L18 32L.025 43.444c.029 1.024.141 2.02.363 2.952L23 32z");
}

.kygipm52i {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M.367 17.684A14.7 14.7 0 0 0 0 21v22c0 1.187.133 2.326.389 3.396L23 32z");
}

.o5s84ubrf {
  fill: var(--svg-color--29b473, #29b473);
  d: path("m15 36.992l-.037-.005L.406 46.455c.892 3.647 3.273 6.447 7.111 7.281L34 37h30V27H34L7.416 10.288c-3.829.874-6.194 3.715-7.051 7.401L15.048 27H15l7 5");
}

.o9olt0bzh {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M35 25L11.73 10H10c-.928 0-1.784.105-2.584.288L34 27h30v-2z");
}

.qkgxembuy {
  fill: var(--svg-color--2b3990, #2b3990);
  d: path("M7.518 53.737c.77.168 1.594.263 2.482.263h44c6.627 0 10-4.925 10-11v-6H34z");
}

.riw60my_f {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M11.849 54L35 39h29v-2H34L7.518 53.737c.77.168 1.594.263 2.482.263z");
}

.vu30ywsla {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M0 37v6c0 1.209.14 2.369.406 3.457L15.762 37zm.365-19.311A14.7 14.7 0 0 0 0 21v6h15.048zM64 27v-6c0-6.075-3.373-11-10-11H10c-.928 0-1.784.105-2.584.288L34 27z");
}

</style>
