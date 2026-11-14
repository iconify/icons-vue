<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o41131usv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hole-in-one" /></template>
<style>
.o41131usv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.25 7.279v6.592q3 1.203 3 3.129q0 1.963-3.114 3.174q-2.767 1.076-6.636 1.076t-6.636-1.076Q1.75 18.963 1.75 17t3.114-3.174q.219-.085.444-.163q.277-.379.626-.729Q7.618 11.25 10 11.25q2.339 0 4.006 1.625q1.469.154 2.744.498V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v.221q.714-.171 1.405.273q.96.616.96 1.756t-.96 1.756q-.691.444-1.405.273m-7.804 5.492q-.219-.021-.446-.021q-.58 0-1.104.135q.749-.082 1.55-.114");
}

</style>
