<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":540};
const content = `<defs><path id="SVGVXm4weGS" class="tw73p2lto"/></defs><path class="vg8_m3bzy"/><path class="i1vsu3q6i"/><g transform="translate(.635 .014)"><mask id="SVGiSBu6dFX" class="n1mjunbsu"><use href="#SVGVXm4weGS"/></mask><path mask="url(#SVGiSBu6dFX)" class="fkwm84hwr"/></g><g transform="translate(.635 .014)"><path mask="url(#SVGiSBu6dFX)" class="rnv6usbrq"/></g><g transform="translate(.635 .014)"><path mask="url(#SVGiSBu6dFX)" class="zrzzr0b3a"/></g><path class="di0u9jr_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:crossplane-icon" /></template>
<style>
.di0u9jr_y {
  fill: var(--svg-color--d8ae64, #d8ae64);
  d: path("m103.448 421.138l55.508 55.645v-56.11z");
}

.fkwm84hwr {
  fill: var(--svg-color--ffcd3c, #ffcd3c);
  d: path("M331.874 126.028L15.19 443.465l-93.79-94.023L238.07 32.006z");
}

.i1vsu3q6i {
  fill: var(--svg-color--ff9234, #ff9234);
  d: path("M255.18 134.095c.185-4.018.185-8.041 0-12.059C252.117 54.114 196.199 0 127.675 0S3.232 54.114.142 122.036a130 130 0 0 0 .014 12.469c-.04 1.066-.15 2.12-.15 3.2v210.042c0 40.168 32.785 73.036 72.858 73.036h109.65c40.058 0 72.843-32.868 72.843-73.036V137.704c0-1.23-.123-2.406-.177-3.61");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.rnv6usbrq {
  fill: var(--svg-color--f3807b, #f3807b);
  d: path("m237.783 31.705l-316.67 317.437l-116.704-116.992L121.052-85.286z");
}

.tw73p2lto {
  d: path("M.137 122.022c-.18 4.155-.172 8.316.027 12.47C.11 135.557 0 136.61 0 137.69v210.042c0 40.169 32.785 73.036 72.858 73.036h109.65c40.058 0 72.857-32.867 72.857-73.036V137.691c0-1.23-.136-2.407-.191-3.61c.199-4.017.204-8.041.014-12.059C252.098 54.1 196.179 0 127.669 0C59.145 0 3.227 54.1.137 122.009z");
}

.vg8_m3bzy {
  fill: var(--svg-color--f7d186, #f7d186);
  d: path("M126.759 173.662c-17.689.03-32.008 14.386-31.993 32.074v301.878a32.034 32.034 0 0 0 31.993 32.074c17.678 0 32.006-14.356 32.006-32.074V205.736c.015-17.688-14.304-32.044-31.993-32.074");
}

.zrzzr0b3a {
  fill: var(--svg-color--35d0ba, #35d0ba);
  d: path("m425.964 220.351l-316.67 317.423l-93.79-94.022l316.671-317.423z");
}

</style>
