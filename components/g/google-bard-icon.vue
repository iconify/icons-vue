<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":258};
const content = `<defs><radialGradient id="SVG1xuhSd8h" cx="78.302%" cy="55.52%" r="78.115%" fx="78.302%" fy="55.52%" gradientTransform="matrix(.19314 .98115 -.98064 .19324 1.176 -.32)"><stop offset="0%" class="lmyxwzfdh"/><stop offset=".01%" class="lmyxwzfdh"/><stop offset="30.022%" class="f6_g6k8nt"/><stop offset="54.552%" class="rcn9wdv5p"/><stop offset="82.537%" class="i6wamq08v"/><stop offset="100%" class="uqd8s_b1v"/></radialGradient><radialGradient id="SVGm6NA5dhq" cx="-3.409%" cy="-54.219%" r="169.363%" fx="-3.409%" fy="-54.219%" gradientTransform="matrix(.19314 .98115 -.98062 .19324 -.56 -.404)"><stop offset="0%" class="lmyxwzfdh"/><stop offset=".01%" class="lmyxwzfdh"/><stop offset="30.022%" class="f6_g6k8nt"/><stop offset="54.552%" class="rcn9wdv5p"/><stop offset="82.537%" class="i6wamq08v"/><stop offset="100%" class="uqd8s_b1v"/></radialGradient></defs><path fill="url(#SVG1xuhSd8h)" class="trraolyjz"/><path fill="url(#SVGm6NA5dhq)" class="zpbl_3jpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-bard-icon" /></template>
<style>
.f6_g6k8nt {
  stop-color: var(--svg-color--5489d6, #5489d6);
}

.i6wamq08v {
  stop-color: var(--svg-color--d96570, #d96570);
}

.lmyxwzfdh {
  stop-color: var(--svg-color--1ba1e3, #1ba1e3);
}

.rcn9wdv5p {
  stop-color: var(--svg-color--9b72cb, #9b72cb);
}

.trraolyjz {
  d: path("m122.062 172.77l-10.27 23.52c-3.947 9.042-16.459 9.042-20.406 0l-10.27-23.52c-9.14-20.933-25.59-37.595-46.108-46.703L6.74 113.52c-8.987-3.99-8.987-17.064 0-21.053l27.385-12.156C55.172 70.97 71.917 53.69 80.9 32.043L91.303 6.977c3.86-9.303 16.712-9.303 20.573 0l10.403 25.066c8.983 21.646 25.728 38.926 46.775 48.268l27.384 12.156c8.987 3.99 8.987 17.063 0 21.053l-28.267 12.547c-20.52 9.108-36.97 25.77-46.109 46.703");
}

.uqd8s_b1v {
  stop-color: var(--svg-color--f49c46, #f49c46);
}

.zpbl_3jpa {
  d: path("m217.5 246.937l-2.888 6.62c-2.114 4.845-8.824 4.845-10.937 0l-2.889-6.62c-5.148-11.803-14.42-21.2-25.992-26.34l-8.898-3.954c-4.811-2.137-4.811-9.131 0-11.269l8.4-3.733c11.87-5.273 21.308-15.017 26.368-27.22l2.966-7.154c2.067-4.985 8.96-4.985 11.027 0l2.966 7.153c5.06 12.204 14.499 21.948 26.368 27.221l8.4 3.733c4.812 2.138 4.812 9.132 0 11.27l-8.898 3.953c-11.571 5.14-20.844 14.537-25.992 26.34");
}

</style>
